<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2xkvt2tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h2xkvt2tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dice-5-fill" /></template>
