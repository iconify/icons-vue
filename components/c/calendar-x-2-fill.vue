<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ix5ia0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ix5ia0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-x-2-fill" /></template>
