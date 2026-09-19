<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs299dt7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vs299dt7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:heart" /></template>
