<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbl0ijbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mbl0ijbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:chess-knight" /></template>
