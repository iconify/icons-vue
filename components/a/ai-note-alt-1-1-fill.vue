<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll_k45b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ll_k45b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-note-alt-1-1-fill" /></template>
