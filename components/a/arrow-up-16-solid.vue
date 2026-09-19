<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk0263b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xk0263b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-16-solid" /></template>
