<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn6qy6jmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zn6qy6jmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:crop" /></template>
