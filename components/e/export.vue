<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcafp3bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jcafp3bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:export" /></template>
