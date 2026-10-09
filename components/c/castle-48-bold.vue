<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz0-7c0kb.css';
import '../../css/j/jf0anfbvm.css';
import '../../css/r/r9l9x_bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oz0-7c0kb"/><path class="jf0anfbvm"/><path class="r9l9x_bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:castle-48-bold" /></template>
