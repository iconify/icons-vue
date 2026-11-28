<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4w3pb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zv4w3pb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:brace-right-duotone" /></template>
