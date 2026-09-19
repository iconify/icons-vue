<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j506mmb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j506mmb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:kitchen-set" /></template>
