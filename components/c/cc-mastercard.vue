<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x324subsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x324subsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-mastercard" /></template>
