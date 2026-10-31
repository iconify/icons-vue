<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozj561beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozj561beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-tree-gloss" /></template>
