<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muzsy9f0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="muzsy9f0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:asset-edit" /></template>
