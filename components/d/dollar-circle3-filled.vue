<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/txu5a_3fa.css';
import '../../css/n/nd3oembfa.css';
import '../../css/d/d4sgmebde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="txu5a_3fa"/><path class="nd3oembfa"/><path class="d4sgmebde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dollar-circle3-filled" /></template>
