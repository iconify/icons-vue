<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxo58abkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mxo58abkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:half-star-1-flat" /></template>
