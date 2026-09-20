<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elhco4bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elhco4bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cash-fill" /></template>
