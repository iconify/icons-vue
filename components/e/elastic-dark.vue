<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwjt238zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwjt238zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:elastic-dark" /></template>
