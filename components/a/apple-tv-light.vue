<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8-j1zyzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t8-j1zyzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple-tv-light" /></template>
