<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq-2l-tup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cq-2l-tup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-ltr" /></template>
