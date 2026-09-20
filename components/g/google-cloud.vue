<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsr7ex80b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsr7ex80b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:google-cloud" /></template>
