<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxi8hkb5i.css';
import '../../css/l/lw72yprve.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/r/r3qvqygmn.css';
import '../../css/z/zt-41go0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxi8hkb5i"/><path clip-rule="evenodd" class="lw72yprve"/><g class="xtpeb-edw"><path class="r3qvqygmn"/><path class="zt-41go0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-round-bold-duotone" /></template>
