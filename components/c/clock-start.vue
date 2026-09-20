<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nta5e4bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nta5e4bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-start" /></template>
