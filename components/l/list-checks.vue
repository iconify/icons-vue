<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucnvjn25j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucnvjn25j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:list-checks" /></template>
