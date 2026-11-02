<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmsi07b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmsi07b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-check-line" /></template>
