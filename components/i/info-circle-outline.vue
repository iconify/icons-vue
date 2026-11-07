<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epahso09d.css';
import '../../css/g/g2-dgp5yi.css';
import '../../css/f/fhxzx1b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epahso09d"/><path class="g2-dgp5yi"/><path clip-rule="evenodd" class="fhxzx1b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:info-circle-outline" /></template>
