<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpzz9abup.css';
import '../../css/z/znd-kf3wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpzz9abup"/><path class="znd-kf3wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:controls-slider-toggle-left" /></template>
