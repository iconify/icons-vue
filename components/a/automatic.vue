<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac-3z-sub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ac-3z-sub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:automatic" /></template>
