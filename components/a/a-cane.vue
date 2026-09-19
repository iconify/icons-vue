<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0b9b_y4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r0b9b_y4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:a-cane" /></template>
