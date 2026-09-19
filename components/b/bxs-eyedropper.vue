<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxc7k61nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxc7k61nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-eyedropper" /></template>
