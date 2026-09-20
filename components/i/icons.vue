<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7_g47bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7_g47bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:icons" /></template>
