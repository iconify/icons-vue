<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_a0h2b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_a0h2b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cake-fill" /></template>
