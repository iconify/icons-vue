<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc30fdcem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="fc30fdcem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:fullscreen-exit" /></template>
