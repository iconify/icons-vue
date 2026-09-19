<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi5gwhbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="xi5gwhbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:credit-card" /></template>
