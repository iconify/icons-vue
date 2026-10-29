<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f__zufvhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f__zufvhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-u" /></template>
