<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za6ahqbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za6ahqbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-x-corner-line" /></template>
