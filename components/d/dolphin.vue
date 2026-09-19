<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbq83e2fr.css';
import '../../css/h/ho8hjnb3u.css';
import '../../css/s/sybk1uw8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xbq83e2fr"/><path class="ho8hjnb3u"/><path class="sybk1uw8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:dolphin" /></template>
