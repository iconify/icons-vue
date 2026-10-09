<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmkt2cc1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cmkt2cc1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-down-20" /></template>
