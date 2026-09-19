<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-1tk425g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-1tk425g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hundredpointssymbol" /></template>
