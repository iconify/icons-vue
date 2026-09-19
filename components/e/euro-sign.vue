<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d06n8p3wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="d06n8p3wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:euro-sign" /></template>
