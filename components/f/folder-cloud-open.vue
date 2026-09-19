<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/p/pvvsmq5js.css';
import '../../css/o/on3hswbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="pvvsmq5js"/><path class="on3hswbab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-cloud-open" /></template>
