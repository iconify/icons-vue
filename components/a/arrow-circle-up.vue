<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e46-ry4zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e46-ry4zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-circle-up" /></template>
