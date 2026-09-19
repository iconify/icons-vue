<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/korjtacdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="korjtacdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:important" /></template>
