<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1_mt0b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z1_mt0b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:building-with-plant" /></template>
