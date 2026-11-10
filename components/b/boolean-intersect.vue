<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0nf99xsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t0nf99xsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:boolean-intersect" /></template>
