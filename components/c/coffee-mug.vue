<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jch-8pb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jch-8pb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:coffee-mug" /></template>
