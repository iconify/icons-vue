<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/unfzw3b8q.css';
import '../../css/f/f9bz07hha.css';
import '../../css/r/rrv638bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="unfzw3b8q"/><rect class="f9bz07hha"/><path clip-rule="evenodd" class="rrv638bwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:battery-full" /></template>
