<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aic02ybsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="aic02ybsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:carbattery" /></template>
