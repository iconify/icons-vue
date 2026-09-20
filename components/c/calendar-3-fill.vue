<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxg9oubsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxg9oubsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-3-fill" /></template>
