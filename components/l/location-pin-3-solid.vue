<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urmzmpbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="urmzmpbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:location-pin-3-solid" /></template>
