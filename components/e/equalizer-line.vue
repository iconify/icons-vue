<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyk6nx-dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyk6nx-dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:equalizer-line" /></template>
