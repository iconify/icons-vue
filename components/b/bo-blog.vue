<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih88xyvhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ih88xyvhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bo-blog" /></template>
