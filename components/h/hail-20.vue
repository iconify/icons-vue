<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5tn1bc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f5tn1bc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hail-20" /></template>
