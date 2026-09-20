<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9jc0ib3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="u9jc0ib3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:flag" /></template>
