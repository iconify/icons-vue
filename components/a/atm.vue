<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu00ooh-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bu00ooh-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:atm" /></template>
