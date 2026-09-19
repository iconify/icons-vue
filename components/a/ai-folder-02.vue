<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlw2aibwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlw2aibwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-folder-02" /></template>
