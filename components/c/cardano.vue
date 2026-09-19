<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjhyc3iad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hjhyc3iad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:cardano" /></template>
