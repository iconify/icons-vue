<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikov2ccdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikov2ccdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flag-outline" /></template>
