<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk_xej3wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk_xej3wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ai-agent-fill" /></template>
