<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-v9j-zlm.css';
import '../../css/t/tsvt3bbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e-v9j-zlm"/><path class="tsvt3bbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-loading-25-percent-1" /></template>
