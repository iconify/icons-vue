<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krsl0u_ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krsl0u_ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:error" /></template>
