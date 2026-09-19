<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmafncc0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kmafncc0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:basket3" /></template>
