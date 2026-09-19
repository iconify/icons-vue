<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqo0f6boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqo0f6boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:like-fill" /></template>
