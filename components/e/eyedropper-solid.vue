<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxrx3cb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxrx3cb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:eyedropper-solid" /></template>
