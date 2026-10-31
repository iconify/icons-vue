<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpa2a4nmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpa2a4nmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-q-bulk-round" /></template>
