<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d81yw8b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d81yw8b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-on-square-stack-20-solid" /></template>
