<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjim-cb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yjim-cb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-voice-duotone" /></template>
