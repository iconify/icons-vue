<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpl049buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpl049buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:columns-3-filled" /></template>
