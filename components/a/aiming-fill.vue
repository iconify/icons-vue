<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tja11q3iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tja11q3iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aiming-fill" /></template>
