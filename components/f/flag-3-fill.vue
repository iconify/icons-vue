<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_19j0b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_19j0b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-3-fill" /></template>
