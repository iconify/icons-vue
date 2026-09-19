<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk36_pgzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sk36_pgzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-double-diagonal-reverse" /></template>
