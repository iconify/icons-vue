<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy6sd3bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="uy6sd3bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:fan" /></template>
