<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfotcudyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lfotcudyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar3-range-fill" /></template>
