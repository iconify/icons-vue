<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfuhywbmz.css';
import '../../css/c/ckv8-4w9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jfuhywbmz"/><path clip-rule="evenodd" class="ckv8-4w9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-time-2" /></template>
