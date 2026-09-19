<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no85bgsgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="no85bgsgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:games" /></template>
