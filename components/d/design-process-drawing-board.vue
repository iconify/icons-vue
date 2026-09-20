<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytj7at_sk.css';
import '../../css/b/b4ouy7bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytj7at_sk"/><path class="b4ouy7bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:design-process-drawing-board" /></template>
