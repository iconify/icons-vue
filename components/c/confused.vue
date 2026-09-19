<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdo4_sr4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdo4_sr4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:confused" /></template>
