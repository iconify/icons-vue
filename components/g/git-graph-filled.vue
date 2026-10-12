<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z69-ohbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z69-ohbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-graph-filled" /></template>
