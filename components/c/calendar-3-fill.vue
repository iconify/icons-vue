<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldg0t_buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldg0t_buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-3-fill" /></template>
