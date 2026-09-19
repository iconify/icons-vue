<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eezel15us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eezel15us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-skipback" /></template>
