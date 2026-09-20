<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq303r2fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq303r2fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-edit-alt-1-line" /></template>
