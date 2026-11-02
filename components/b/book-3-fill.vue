<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpy4_z3jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpy4_z3jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-3-fill" /></template>
