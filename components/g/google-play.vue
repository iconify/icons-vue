<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpwh6abex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zpwh6abex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:google-play" /></template>
