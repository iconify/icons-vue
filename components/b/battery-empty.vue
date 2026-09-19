<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1ao6026r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ao6026r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:battery-empty" /></template>
