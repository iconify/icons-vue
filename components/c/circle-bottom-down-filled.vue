<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a2pqnabsm.css';
import '../../css/o/o7_zbclrn.css';
import '../../css/t/tjq12i1zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a2pqnabsm"/><path clip-rule="evenodd" class="o7_zbclrn"/><path class="tjq12i1zh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-bottom-down-filled" /></template>
