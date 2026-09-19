<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmzuscc9w.css';
import '../../css/o/oynddubhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fmzuscc9w"/><path class="oynddubhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-exit" /></template>
