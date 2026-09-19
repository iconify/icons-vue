<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwm_mmbgi.css';
import '../../css/h/hwy34kbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lwm_mmbgi"/><path class="hwy34kbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-battery-dead" /></template>
