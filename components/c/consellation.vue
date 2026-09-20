<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnh3mtb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnh3mtb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:consellation" /></template>
