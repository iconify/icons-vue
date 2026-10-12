<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wupo9cczk.css';
import '../../css/b/bubgyx1xt.css';
import '../../css/e/e-arpva-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wupo9cczk"/><path class="bubgyx1xt"/><path class="e-arpva-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lathe-48-bold" /></template>
