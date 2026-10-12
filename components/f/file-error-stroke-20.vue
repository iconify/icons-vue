<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_jbvkbbv.css';
import '../../css/y/ypv4l3ivv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j_jbvkbbv"/><path class="ypv4l3ivv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-error-stroke-20" /></template>
