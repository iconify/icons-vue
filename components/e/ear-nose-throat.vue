<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haxvedcdm.css';
import '../../css/a/alb_3ybms.css';
import '../../css/e/eu7poe5sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="haxvedcdm"/><path class="alb_3ybms"/><path class="eu7poe5sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:ear-nose-throat" /></template>
