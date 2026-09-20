<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncm1w2prn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncm1w2prn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flashpaper-light" /></template>
