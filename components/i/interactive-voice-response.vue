<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvp85bpbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvp85bpbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:interactive-voice-response" /></template>
