<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ygox79bep.css';
import '../../css/z/zy_fdbc1g.css';
import '../../css/j/jbrxmkbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="ygox79bep"/><path class="zy_fdbc1g"/><path class="jbrxmkbnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:lock-light" /></template>
