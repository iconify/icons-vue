<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_cor3_8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_cor3_8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bold-circle" /></template>
