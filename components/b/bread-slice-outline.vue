<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytbpjhtjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytbpjhtjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bread-slice-outline" /></template>
