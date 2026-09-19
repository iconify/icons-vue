<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k1n3gmbxo.css';
import '../../css/w/wnocnbc7k.css';
import '../../css/f/fvlkw7bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="k1n3gmbxo"/><path class="wnocnbc7k"/><path class="fvlkw7bxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:edit-movie" /></template>
