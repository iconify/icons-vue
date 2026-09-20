<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecf22k6ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ecf22k6ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:betula" /></template>
