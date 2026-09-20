<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onpq72bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="onpq72bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:instance-ltr" /></template>
