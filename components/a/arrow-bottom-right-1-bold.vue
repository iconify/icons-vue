<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekbpro7fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekbpro7fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-right-1-bold" /></template>
