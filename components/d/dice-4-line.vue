<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpjio5o_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpjio5o_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-4-line" /></template>
