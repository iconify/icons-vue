<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1m0pe8ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a1m0pe8ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-vis-2" /></template>
