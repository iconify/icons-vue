<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj6a84bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj6a84bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cellphone-play" /></template>
