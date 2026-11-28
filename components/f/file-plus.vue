<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlyk6t44o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlyk6t44o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-plus" /></template>
