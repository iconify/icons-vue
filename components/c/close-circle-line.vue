<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_wq8_b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_wq8_b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:close-circle-line" /></template>
