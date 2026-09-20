<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrwvep5rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qrwvep5rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ai-generate-voice-robot-2-remix" /></template>
