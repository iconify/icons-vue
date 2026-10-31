<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slkviu_2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="slkviu_2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-in-eaved-gabled-building" /></template>
