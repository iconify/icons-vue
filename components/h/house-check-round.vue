<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0qfcro3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0qfcro3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-check-round" /></template>
