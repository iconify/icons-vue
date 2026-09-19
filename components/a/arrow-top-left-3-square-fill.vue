<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr5x2bcqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cr5x2bcqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-3-square-fill" /></template>
