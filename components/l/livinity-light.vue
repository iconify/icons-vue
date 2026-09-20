<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-sjs80hz.css';
import '../../css/y/yg4ntub0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-sjs80hz"/><circle class="yg4ntub0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:livinity-light" /></template>
