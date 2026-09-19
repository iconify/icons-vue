<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3tnoebhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":432};
const content = `<path class="n3tnoebhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hourglass-alt" /></template>
