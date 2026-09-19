<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-e8mbbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-e8mbbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar-x" /></template>
