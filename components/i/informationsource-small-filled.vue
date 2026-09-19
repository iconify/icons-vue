<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv68dpb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bv68dpb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:informationsource-small-filled" /></template>
