<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxy9z3b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cxy9z3b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:calc" /></template>
