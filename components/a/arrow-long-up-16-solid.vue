<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_hzqnb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y_hzqnb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-up-16-solid" /></template>
