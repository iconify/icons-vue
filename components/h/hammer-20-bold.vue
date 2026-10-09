<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soxs6zviv.css';
import '../../css/v/vjp44lm8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="soxs6zviv"/><path class="vjp44lm8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hammer-20-bold" /></template>
