<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1g_tcb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s1g_tcb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:electric-cord-3-remix" /></template>
