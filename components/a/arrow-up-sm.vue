<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-69xffvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-69xffvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-up-sm" /></template>
