<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnr7fptxp.css';
import '../../css/w/wl2c1p1go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnr7fptxp"/><path class="wl2c1p1go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:feed" /></template>
