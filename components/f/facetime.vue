<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/o3asidbga.css';
import '../../css/i/i3_wdu1cq.css';
import '../../css/a/aw5cy6wrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="o3asidbga"/><path class="i3_wdu1cq"/><path class="aw5cy6wrw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:facetime" /></template>
