<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6_x74bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6_x74bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cake-fill" /></template>
