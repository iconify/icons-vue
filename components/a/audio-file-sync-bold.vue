<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mssq4ub0k.css';
import '../../css/l/lkvs5hb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mssq4ub0k"/><path class="lkvs5hb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:audio-file-sync-bold" /></template>
