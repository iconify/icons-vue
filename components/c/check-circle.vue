<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td6n-mrnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td6n-mrnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:check-circle" /></template>
