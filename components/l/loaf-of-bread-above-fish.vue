<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6_6e0udu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x6_6e0udu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:loaf-of-bread-above-fish" /></template>
