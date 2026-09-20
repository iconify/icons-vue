<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in57chbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in57chbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:location-3" /></template>
