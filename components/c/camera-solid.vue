<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re3_sbpib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re3_sbpib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:camera-solid" /></template>
