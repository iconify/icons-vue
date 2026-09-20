<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv0akdb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv0akdb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:align-right" /></template>
