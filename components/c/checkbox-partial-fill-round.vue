<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-cd_q5uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cd_q5uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-partial-fill-round" /></template>
