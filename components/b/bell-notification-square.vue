<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/v/vj567d7up.css';
import '../../css/m/mcojq7b_o.css';
import '../../css/z/z7h9dmbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="vj567d7up"/><path class="mcojq7b_o"/><rect class="z7h9dmbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bell-notification-square" /></template>
