<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cead6bcoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cead6bcoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:heading" /></template>
