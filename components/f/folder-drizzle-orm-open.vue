<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/o/o_z6xgmcq.css';
import '../../css/i/i4xym8b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path transform="matrix(.8418 0 0 .8401 14.11 4.099)" class="o_z6xgmcq"/><path class="i4xym8b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-drizzle-orm-open" /></template>
