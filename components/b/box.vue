<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zie4bybop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zie4bybop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:box" /></template>
