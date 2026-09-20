<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnkyu7bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dnkyu7bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:location-pin-3-remix" /></template>
