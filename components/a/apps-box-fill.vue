<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvzur6duk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tvzur6duk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:apps-box-fill" /></template>
