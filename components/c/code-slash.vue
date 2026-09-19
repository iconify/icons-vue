<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-lg61cte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-lg61cte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:code-slash" /></template>
