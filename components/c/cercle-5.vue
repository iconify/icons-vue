<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i01g5y-bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i01g5y-bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-5" /></template>
