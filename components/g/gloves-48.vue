<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weojyq1pz.css';
import '../../css/x/xv0lvbb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="weojyq1pz"/><path class="xv0lvbb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gloves-48" /></template>
