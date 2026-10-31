<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_uv1bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1_uv1bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-lightning-round" /></template>
