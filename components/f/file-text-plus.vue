<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7qva2z3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7qva2z3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-plus" /></template>
