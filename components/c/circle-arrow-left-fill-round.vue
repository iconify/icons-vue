<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh8av2-8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh8av2-8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-left-fill-round" /></template>
