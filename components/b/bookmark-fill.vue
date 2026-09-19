<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6-now6rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6-now6rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bookmark-fill" /></template>
