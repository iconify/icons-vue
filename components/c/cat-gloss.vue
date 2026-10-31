<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i31cdc05h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i31cdc05h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cat-gloss" /></template>
