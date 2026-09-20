<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtyomgb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtyomgb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codex-openai" /></template>
