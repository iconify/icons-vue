<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id-dlnwlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="id-dlnwlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:garage" /></template>
