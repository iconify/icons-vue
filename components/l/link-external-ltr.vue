<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsmongb3e.css';
import '../../css/r/r_bfxptlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jsmongb3e"/><path class="r_bfxptlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:link-external-ltr" /></template>
