<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncjysacrn.css';
import '../../css/i/ialpo-rom.css';
import '../../css/f/fks66gnvh.css';
import '../../css/d/d6a34cbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="ncjysacrn"/><path class="ialpo-rom"/><circle class="fks66gnvh"/><circle class="d6a34cbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:bad" /></template>
