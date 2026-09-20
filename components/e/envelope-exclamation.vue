<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shcnkrbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shcnkrbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-exclamation" /></template>
