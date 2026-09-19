<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ij-6bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="c7ij-6bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:long-arrow-alt-up" /></template>
