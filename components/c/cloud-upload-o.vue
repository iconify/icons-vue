<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs3uvlr_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs3uvlr_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:cloud-upload-o" /></template>
