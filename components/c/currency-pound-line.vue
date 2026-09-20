<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu55nd1hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu55nd1hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-pound-line" /></template>
