<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emor5sbck.css';
import '../../css/e/eai8xpb2c.css';
import '../../css/q/qdn8ggbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="emor5sbck"/><path class="eai8xpb2c"/><path class="qdn8ggbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intrusion-prevention" /></template>
