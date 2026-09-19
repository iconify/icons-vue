<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2shcvb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d2shcvb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ferry" /></template>
