<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkhgmop_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mkhgmop_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:abt" /></template>
