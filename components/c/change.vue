<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/aqa5dpbyw.css';
import '../../css/y/y3-2rob4h.css';
import '../../css/r/r_pad0b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="aqa5dpbyw"/><path class="y3-2rob4h"/><path class="r_pad0b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:change" /></template>
