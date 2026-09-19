<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4tsa95tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g4tsa95tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-left-20-solid" /></template>
