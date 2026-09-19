<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0eeupfys.css';
import '../../css/w/ws8a0lt4p.css';
import '../../css/s/sr-_ec-wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0eeupfys"/><path class="ws8a0lt4p"/><path class="sr-_ec-wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:document-attach-outline" /></template>
