<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0-k71zpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0-k71zpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-to-top" /></template>
