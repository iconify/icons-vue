<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12ji_bzg.css';
import '../../css/v/vc4wxe89z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i12ji_bzg"/><path class="vc4wxe89z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-azure-devops-open" /></template>
