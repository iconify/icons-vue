<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm1bh9b5l.css';
import '../../css/n/n3p0cac3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1bh9b5l"/><path clip-rule="evenodd" class="n3p0cac3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-fact-alt-1-fill" /></template>
