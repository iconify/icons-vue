<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amw_g50ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="amw_g50ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:comment-compact" /></template>
