<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc0js2y2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fc0js2y2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fingerprint-2-solid" /></template>
