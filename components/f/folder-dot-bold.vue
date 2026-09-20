<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0q0dtbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u0q0dtbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-dot-bold" /></template>
