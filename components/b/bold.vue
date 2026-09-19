<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mefe3absu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mefe3absu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bold" /></template>
