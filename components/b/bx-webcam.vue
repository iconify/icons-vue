<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj2h69bvg.css';
import '../../css/x/x0l9201mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj2h69bvg"/><path class="x0l9201mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-webcam" /></template>
