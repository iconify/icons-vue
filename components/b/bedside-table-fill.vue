<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suzek1byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suzek1byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bedside-table-fill" /></template>
