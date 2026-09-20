<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hegyw304a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hegyw304a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ai-generate-voice-robot-2-solid" /></template>
