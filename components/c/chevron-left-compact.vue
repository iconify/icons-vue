<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd53c6jcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hd53c6jcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chevron-left-compact" /></template>
