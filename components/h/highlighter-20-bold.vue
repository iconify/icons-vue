<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o14cv2k9c.css';
import '../../css/e/eryruythf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o14cv2k9c"/><path class="eryruythf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:highlighter-20-bold" /></template>
