<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb2av2t2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":30};
const content = `<path clip-rule="evenodd" class="wb2av2t2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inngest-dark" /></template>
