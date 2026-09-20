<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0arkwy6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0arkwy6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-ai-2-fill" /></template>
