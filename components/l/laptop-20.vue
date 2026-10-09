<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m72yo6b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m72yo6b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laptop-20" /></template>
