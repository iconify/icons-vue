<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_j62hbkk.css';
import '../../css/o/ovv75xbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_j62hbkk"/><path clip-rule="evenodd" class="ovv75xbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-note-fill" /></template>
