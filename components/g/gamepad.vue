<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/une91sbso.css';
import '../../css/c/cbpc7btec.css';
import '../../css/l/lsfe1172a.css';
import '../../css/s/s0ed558ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="une91sbso wm-shadow"/><path class="cbpc7btec wm-shadow"/><path class="lsfe1172a"/><path class="s0ed558ma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:gamepad" /></template>
