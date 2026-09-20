<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_fblebdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_fblebdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fitness-fill" /></template>
