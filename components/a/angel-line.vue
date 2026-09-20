<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmyvicqic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmyvicqic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:angel-line" /></template>
