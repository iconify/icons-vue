<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkxaczbdn.css';
import '../../css/a/ad8m3acwq.css';
import '../../css/a/apgdcwqaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wkxaczbdn"/><path class="ad8m3acwq"/><path class="apgdcwqaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carrot-20" /></template>
