<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5ruenrdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m5ruenrdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:focus-frame-solid" /></template>
