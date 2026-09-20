<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh8lsuzqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mh8lsuzqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:box-1" /></template>
