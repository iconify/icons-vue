<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za8a9ld3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="za8a9ld3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:interactive-voice-response-filled" /></template>
