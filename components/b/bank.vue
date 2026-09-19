<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ibkr3co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ibkr3co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:bank" /></template>
