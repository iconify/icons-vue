<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iugweob7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iugweob7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:codeproject-ai-server-light" /></template>
