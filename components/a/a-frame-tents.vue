<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewf1vbbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ewf1vbbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:a-frame-tents" /></template>
