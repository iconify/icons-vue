<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf-uo8pvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-uo8pvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-code-round" /></template>
