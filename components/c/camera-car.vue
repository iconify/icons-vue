<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgkxl_bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgkxl_bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:camera-car" /></template>
