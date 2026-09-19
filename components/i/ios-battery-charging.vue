<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwm_mmbgi.css';
import '../../css/h/hwy34kbyx.css';
import '../../css/j/j-4ki410r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lwm_mmbgi"/><path class="hwy34kbyx"/><path class="j-4ki410r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-battery-charging" /></template>
