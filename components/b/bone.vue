<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9xnv8bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9xnv8bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bone" /></template>
