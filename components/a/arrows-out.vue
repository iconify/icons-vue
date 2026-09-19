<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9pqwaceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="p9pqwaceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:arrows-out" /></template>
