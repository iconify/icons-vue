<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvqk40bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xvqk40bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:button-power-1-solid" /></template>
