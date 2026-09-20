<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpt2--6uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jpt2--6uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:check" /></template>
