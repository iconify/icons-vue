<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx-rqibfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rx-rqibfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:building" /></template>
