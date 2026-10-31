<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfj06-b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfj06-b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-left-down-bulk-round" /></template>
