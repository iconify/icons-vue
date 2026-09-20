<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbw-nrqom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbw-nrqom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cloudy-rain-filled" /></template>
