<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufttswxdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufttswxdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:gym" /></template>
