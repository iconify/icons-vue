<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmemd-bvx.css';
import '../../css/a/as_el_bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qmemd-bvx"/><path class="as_el_bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:battery-empty" /></template>
