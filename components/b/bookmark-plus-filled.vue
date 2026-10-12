<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nockl6-tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nockl6-tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bookmark-plus-filled" /></template>
