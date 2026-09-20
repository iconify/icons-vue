<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az0avhbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az0avhbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diversify" /></template>
