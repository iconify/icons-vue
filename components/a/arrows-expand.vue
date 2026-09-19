<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj_clkr6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bj_clkr6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:arrows-expand" /></template>
