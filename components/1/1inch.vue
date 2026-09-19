<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9s38sb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b9s38sb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:1inch" /></template>
