<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vayrid8hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vayrid8hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:inbox-line" /></template>
