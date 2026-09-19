<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfs9dqbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kfs9dqbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:magnifying-glass-minus" /></template>
