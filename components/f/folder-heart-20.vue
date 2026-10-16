<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3me-4caq.css';
import '../../css/o/oixzy0brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c3me-4caq"/><path class="oixzy0brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-heart-20" /></template>
