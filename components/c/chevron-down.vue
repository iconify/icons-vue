<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d70qsmb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d70qsmb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-down" /></template>
