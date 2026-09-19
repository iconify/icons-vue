<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/j7c14g7jg.css';
import '../../css/x/xg4m4rbsj.css';
import '../../css/f/fo4q8_bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="j7c14g7jg"/><rect class="xg4m4rbsj"/><rect transform="matrix(1 0 0 -1 9.5 14.5)" class="fo4q8_bnm"/><rect transform="matrix(1 0 0 -1 13 14.5)" class="fo4q8_bnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:devices-outline" /></template>
