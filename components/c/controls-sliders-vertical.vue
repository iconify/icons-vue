<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvtef0brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvtef0brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:controls-sliders-vertical" /></template>
