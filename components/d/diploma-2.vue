<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz509tbyc.css';
import '../../css/y/yvlrv4bki.css';
import '../../css/m/mj4jn0bjh.css';
import '../../css/d/dmz258btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uz509tbyc"/><path class="yvlrv4bki"/><path class="mj4jn0bjh"/><path class="dmz258btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:diploma-2" /></template>
