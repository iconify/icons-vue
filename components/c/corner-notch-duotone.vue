<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfempqb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zfempqb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-notch-duotone" /></template>
