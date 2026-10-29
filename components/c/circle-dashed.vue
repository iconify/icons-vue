<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot8g76bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot8g76bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:circle-dashed" /></template>
