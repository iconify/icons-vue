<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcpug3b7d.css';
import '../../css/w/wvt4upzll.css';
import '../../css/r/rfmo84bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcpug3b7d"/><path class="wvt4upzll"/><path class="rfmo84bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:chartupwardstrend" /></template>
