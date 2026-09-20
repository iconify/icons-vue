<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hknxp1bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hknxp1bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bitcoin-sv" /></template>
