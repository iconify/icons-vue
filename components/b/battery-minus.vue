<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqd65yb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqd65yb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:battery-minus" /></template>
