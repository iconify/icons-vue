<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aemgsmjzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aemgsmjzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-lock-open" /></template>
