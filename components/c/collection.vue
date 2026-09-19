<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msau2_b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="msau2_b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:collection" /></template>
