<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt8y22vno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt8y22vno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-assistant" /></template>
