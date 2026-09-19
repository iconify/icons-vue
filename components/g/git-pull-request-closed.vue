<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l1hgzkxik.css';
import '../../css/s/sa8oq8bea.css';
import '../../css/n/ng521n2fi.css';
import '../../css/n/nmoouyb9r.css';
import '../../css/x/xywnlchxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l1hgzkxik"/><circle class="sa8oq8bea"/><circle class="ng521n2fi"/><circle class="nmoouyb9r"/><path class="xywnlchxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:git-pull-request-closed" /></template>
