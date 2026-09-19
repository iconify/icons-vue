<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndh7-hb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ndh7-hb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-up" /></template>
