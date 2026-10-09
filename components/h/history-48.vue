<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8xbdfbrh.css';
import '../../css/h/hok4abbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v8xbdfbrh"/><path class="hok4abbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:history-48" /></template>
