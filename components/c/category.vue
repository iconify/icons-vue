<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-6i0-bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-6i0-bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:category" /></template>
