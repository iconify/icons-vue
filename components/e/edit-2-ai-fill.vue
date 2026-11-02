<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bes95g4qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bes95g4qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-2-ai-fill" /></template>
