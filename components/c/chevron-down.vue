<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sivxnq7wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sivxnq7wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-down" /></template>
