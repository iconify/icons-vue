<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/ryy5dkt3h.css';
import '../../css/r/r9qeinbko.css';
import '../../css/j/j5e0pebko.css';
import '../../css/v/vt4fvacch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ryy5dkt3h"/><path class="r9qeinbko wm-a"/><path class="j5e0pebko wm-k"/><path class="vt4fvacch wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-x-sketch" /></template>
