<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7tq0rbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7tq0rbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-arrow-up" /></template>
