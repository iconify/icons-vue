<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usn_kpbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="usn_kpbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:five" /></template>
