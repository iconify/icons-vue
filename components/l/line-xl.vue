<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akp48p50j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akp48p50j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:line-xl" /></template>
