<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfzmct09b.css';
import '../../css/x/xkn94gxsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<path class="lfzmct09b"/><circle class="xkn94gxsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:docuseal" /></template>
