<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0g6_5b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e0g6_5b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:louisiana" /></template>
