<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw81v4b0k.css';
import '../../css/k/kx-x5p24u.css';
import '../../css/t/tah-fgebz.css';
import '../../css/q/qsti3bbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cw81v4b0k"/><path class="kx-x5p24u"/><path class="tah-fgebz"/><path class="qsti3bbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gantry-crane-48-bold" /></template>
