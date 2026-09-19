<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp6ev7bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jp6ev7bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bell-20-solid" /></template>
