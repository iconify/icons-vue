<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnq2fg_cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xnq2fg_cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hierarchy-16-remix" /></template>
