<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8hod8bsp.css';
import '../../css/n/nruyxmb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8hod8bsp"/><path class="nruyxmb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-right-stroke-square" /></template>
