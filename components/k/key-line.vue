<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4_m7ebys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4_m7ebys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:key-line" /></template>
