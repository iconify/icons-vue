<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb6fqubbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eb6fqubbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:chevron-top" /></template>
