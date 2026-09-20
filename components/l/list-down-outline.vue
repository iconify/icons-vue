<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obee10aza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obee10aza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-down-outline" /></template>
