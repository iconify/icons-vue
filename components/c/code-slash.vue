<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm61msbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sm61msbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:code-slash" /></template>
