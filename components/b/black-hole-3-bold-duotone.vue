<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn_05tynm.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/a/ah45prb2d.css';
import '../../css/e/en7qtqbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn_05tynm"/><g class="xtpeb-edw"><path class="ah45prb2d"/><path class="en7qtqbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-3-bold-duotone" /></template>
