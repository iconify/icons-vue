<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7ijr0lpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k7ijr0lpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:jump-alt" /></template>
