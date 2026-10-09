<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo6miub8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vo6miub8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-left-20" /></template>
