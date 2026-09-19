<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl3pk4bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gl3pk4bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:amd" /></template>
