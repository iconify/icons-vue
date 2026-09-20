<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6q1_pb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6q1_pb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-3-ai-fill" /></template>
