<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ollll1rvu.css';
import '../../css/s/ssk_xhn8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ollll1rvu"/><path class="ssk_xhn8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:flower" /></template>
