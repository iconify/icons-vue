<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8v-evrrq.css';
import '../../css/d/d9ypmmcan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o8v-evrrq"/><path class="d9ypmmcan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-awesome" /></template>
