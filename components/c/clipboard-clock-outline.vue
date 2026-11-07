<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxkbezb3a.css';
import '../../css/e/e3rn21oia.css';
import '../../css/l/lz2l27i1w.css';
import '../../css/n/n9livpbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxkbezb3a"/><path class="e3rn21oia"/><path class="lz2l27i1w"/><path class="n9livpbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-clock-outline" /></template>
