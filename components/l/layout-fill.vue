<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vepxg1bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vepxg1bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-fill" /></template>
