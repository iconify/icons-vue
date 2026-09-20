<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwgmc0e6k.css';
import '../../css/i/ipamtibyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hwgmc0e6k"/><path class="ipamtibyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoke-ai" /></template>
