<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s7qxfdbrb.css';
import '../../css/h/hwsal5q-o.css';
import '../../css/z/ze6eu2fom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s7qxfdbrb"/><circle class="hwsal5q-o"/><path class="ze6eu2fom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hand-brake" /></template>
