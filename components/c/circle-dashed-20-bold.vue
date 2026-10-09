<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emm9a3bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="emm9a3bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circle-dashed-20-bold" /></template>
