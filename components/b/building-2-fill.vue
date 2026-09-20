<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi0mlsb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mi0mlsb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-2-fill" /></template>
