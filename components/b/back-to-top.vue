<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-9ms3tgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k-9ms3tgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:back-to-top" /></template>
