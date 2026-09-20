<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9p30owtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9p30owtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gas-station-fill" /></template>
