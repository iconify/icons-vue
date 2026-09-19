<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8xhx3bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="a8xhx3bap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:home" /></template>
