<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iux_xg0hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iux_xg0hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bank-vault" /></template>
