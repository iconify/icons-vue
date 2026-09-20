<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg403wb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="hg403wb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:ball-point-pen" /></template>
