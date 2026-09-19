<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmwzwvbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vmwzwvbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-2" /></template>
