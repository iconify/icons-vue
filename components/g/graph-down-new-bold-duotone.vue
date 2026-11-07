<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/f/f64xfybyo.css';
import '../../css/y/yp5dl9p5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="f64xfybyo"/><path class="yp5dl9p5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-down-new-bold-duotone" /></template>
