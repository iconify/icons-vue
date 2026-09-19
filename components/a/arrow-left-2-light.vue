<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_pfi2b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_pfi2b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-2-light" /></template>
