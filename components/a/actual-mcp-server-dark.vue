<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhjc_3plp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qhjc_3plp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:actual-mcp-server-dark" /></template>
