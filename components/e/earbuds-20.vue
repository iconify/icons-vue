<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9b3_-bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m9b3_-bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earbuds-20" /></template>
