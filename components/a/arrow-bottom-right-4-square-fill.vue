<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7i42jxaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7i42jxaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-4-square-fill" /></template>
