<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcsnbtokg.css';
import '../../css/f/fffxy750p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="dcsnbtokg"/><path class="fffxy750p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:loops" /></template>
