<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz98x5bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz98x5bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-plus-fill-round" /></template>
