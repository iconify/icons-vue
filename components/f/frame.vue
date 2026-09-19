<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6hhcjbid.css';
import '../../css/r/ryyiu8v4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6hhcjbid"/><path class="ryyiu8v4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:frame" /></template>
