<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwuvc_gqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jwuvc_gqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:good-health-and-well-being-solid" /></template>
