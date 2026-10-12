<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa_--1afw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa_--1afw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-chevron-left-filled" /></template>
