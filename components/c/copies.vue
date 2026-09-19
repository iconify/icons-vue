<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zawx550ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zawx550ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:copies" /></template>
