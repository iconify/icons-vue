<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekvdh_bjk.css';
import '../../css/n/n5smlmpfr.css';
import '../../css/j/j3985abug.css';
import '../../css/d/dclgqfbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ekvdh_bjk"/><path class="n5smlmpfr"/><circle class="j3985abug"/><path class="dclgqfbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:currency-exchange" /></template>
