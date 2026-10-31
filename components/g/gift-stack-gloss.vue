<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czkks7lgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czkks7lgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gift-stack-gloss" /></template>
