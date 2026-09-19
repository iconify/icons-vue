<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xit4yh0_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xit4yh0_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:line-height" /></template>
