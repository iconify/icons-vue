<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag1m98bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ag1m98bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:arrow-up" /></template>
