<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhwf4_tkf.css';
import '../../css/y/ydubk1bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vhwf4_tkf"/><path class="ydubk1bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:funnel-ltr" /></template>
