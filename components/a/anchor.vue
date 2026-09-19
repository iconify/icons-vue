<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stcan_o_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="stcan_o_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:anchor" /></template>
