<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbnvaacxi.css';
import '../../css/b/bgnsygbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tbnvaacxi"/><path class="bgnsygbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:duplicate" /></template>
