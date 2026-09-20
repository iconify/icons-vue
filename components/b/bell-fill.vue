<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2ia15bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2ia15bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bell-fill" /></template>
