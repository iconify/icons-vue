<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd0zhtbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hd0zhtbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-bottom-left" /></template>
