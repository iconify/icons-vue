<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy8rokwbh.css';
import '../../css/e/eajtpz02m.css';
import '../../css/q/qxwq8bcbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jy8rokwbh"/><path class="eajtpz02m"/><path class="qxwq8bcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-manager-light" /></template>
