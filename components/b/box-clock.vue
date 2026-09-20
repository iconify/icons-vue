<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1q40isfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1q40isfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-clock" /></template>
