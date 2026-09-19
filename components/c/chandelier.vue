<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pil6s8bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pil6s8bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:chandelier" /></template>
