<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2iip6b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2iip6b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:group-resource" /></template>
