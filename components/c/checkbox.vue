<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk68ltbne.css';
import '../../css/a/a0xb5cbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="nk68ltbne"/><path class="a0xb5cbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:checkbox" /></template>
