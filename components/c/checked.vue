<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh5vy0b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="eh5vy0b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:checked" /></template>
