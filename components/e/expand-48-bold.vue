<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk_btpb8m.css';
import '../../css/s/s-anv9bde.css';
import '../../css/h/hfommxotc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gk_btpb8m"/><path class="s-anv9bde"/><path class="hfommxotc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:expand-48-bold" /></template>
