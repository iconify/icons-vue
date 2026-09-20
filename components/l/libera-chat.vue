<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqo7mbvlt.css';
import '../../css/s/syv4ombst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqo7mbvlt"/><path class="syv4ombst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libera-chat" /></template>
