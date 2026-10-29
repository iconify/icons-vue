<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l12p6vo3k.css';
import '../../css/q/qqmov0t5w.css';
import '../../css/g/grharab0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l12p6vo3k wm-k"/><path class="qqmov0t5w wm-k"/><path class="grharab0w wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:cloud-lightning" /></template>
