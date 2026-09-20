<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_1d6ub_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_1d6ub_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flash-auto" /></template>
