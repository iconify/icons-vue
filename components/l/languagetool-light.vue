<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc9xcibsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fc9xcibsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:languagetool-light" /></template>
