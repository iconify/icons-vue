<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5bk2nbef.css';
import '../../css/b/bdjsbobgf.css';
import '../../css/w/whrxjkbma.css';
import '../../css/t/tgzsbh4mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t5bk2nbef"/><path class="bdjsbobgf"/><path class="whrxjkbma"/><path class="tgzsbh4mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-station-20" /></template>
