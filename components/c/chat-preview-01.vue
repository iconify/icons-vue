<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/ws7tt80dx.css';
import '../../css/u/ufw1mbb_w.css';
import '../../css/m/mphyl5x1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ws7tt80dx"/><path class="ufw1mbb_w"/><path class="mphyl5x1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chat-preview-01" /></template>
