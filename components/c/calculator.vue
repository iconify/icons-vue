<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzmfcm04q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzmfcm04q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calculator" /></template>
