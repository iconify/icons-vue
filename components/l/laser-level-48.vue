<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkry5yh6w.css';
import '../../css/v/vt7mt9-ct.css';
import '../../css/w/wl8gimjuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bkry5yh6w"/><path class="vt7mt9-ct"/><path class="wl8gimjuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laser-level-48" /></template>
