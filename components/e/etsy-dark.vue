<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnv50rb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hnv50rb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:etsy-dark" /></template>
