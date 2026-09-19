<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbqzj5bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="wbqzj5bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chevron-circle-left" /></template>
