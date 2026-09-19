<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn0e0ac1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn0e0ac1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:elder" /></template>
