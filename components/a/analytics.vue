<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e74j4sj4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e74j4sj4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:analytics" /></template>
