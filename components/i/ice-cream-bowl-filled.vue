<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdmj-0wpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdmj-0wpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ice-cream-bowl-filled" /></template>
