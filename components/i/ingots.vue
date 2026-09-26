<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khnu7pbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="khnu7pbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:ingots" /></template>
