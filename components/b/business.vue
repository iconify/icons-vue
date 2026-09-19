<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqvm3jumk.css';
import '../../css/x/x2fozm4ep.css';
import '../../css/f/fqwabbb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xqvm3jumk"/><path class="x2fozm4ep"/><path class="fqwabbb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:business" /></template>
