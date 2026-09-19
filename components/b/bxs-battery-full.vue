<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0nd1b7at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0nd1b7at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-battery-full" /></template>
