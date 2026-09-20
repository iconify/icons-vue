<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_j62hbkk.css';
import '../../css/c/c9v861dmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_j62hbkk"/><path clip-rule="evenodd" class="c9v861dmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-note-1-fill" /></template>
