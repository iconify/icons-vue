<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvgqr2t8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvgqr2t8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up-1-0" /></template>
