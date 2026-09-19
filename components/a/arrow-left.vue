<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylo1qp7ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ylo1qp7ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-left" /></template>
