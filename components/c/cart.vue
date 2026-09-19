<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/en701kbcf.css';
import '../../css/b/bsy36b7su.css';
import '../../css/l/ln68z2bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="en701kbcf"/><circle class="bsy36b7su"/><path class="ln68z2bzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:cart" /></template>
