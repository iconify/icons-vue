<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb6gjezva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hb6gjezva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:compass-dashboard-dark" /></template>
