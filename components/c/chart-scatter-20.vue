<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9nmtab-x.css';
import '../../css/b/bkmbl7bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l9nmtab-x"/><path class="bkmbl7bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-scatter-20" /></template>
