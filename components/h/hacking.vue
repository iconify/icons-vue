<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/f/f2wcktryo.css';
import '../../css/f/f_056cc9h.css';
import '../../css/i/i-qglfbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="f2wcktryo"/><path class="f_056cc9h"/></g><path class="i-qglfbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:hacking" /></template>
