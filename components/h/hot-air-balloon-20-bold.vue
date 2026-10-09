<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wupsqfb9m.css';
import '../../css/s/slmd-2blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wupsqfb9m"/><path class="slmd-2blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-air-balloon-20-bold" /></template>
