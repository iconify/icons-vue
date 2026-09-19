<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf17anogk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hf17anogk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:layers" /></template>
