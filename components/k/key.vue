<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn_fvc00b.css';
import '../../css/s/splbbwb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wn_fvc00b"/><circle class="splbbwb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:key" /></template>
