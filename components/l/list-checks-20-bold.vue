<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjw_5r1kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vjw_5r1kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:list-checks-20-bold" /></template>
