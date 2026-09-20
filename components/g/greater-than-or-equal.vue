<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij26ksgsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij26ksgsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:greater-than-or-equal" /></template>
