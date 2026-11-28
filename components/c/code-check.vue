<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byhf100bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byhf100bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:code-check" /></template>
