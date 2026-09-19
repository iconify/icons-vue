<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo5uhngrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo5uhngrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:align-center-v" /></template>
