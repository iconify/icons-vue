<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt_08xbdc.css';
import '../../css/e/e1l_1_bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pt_08xbdc"/><path class="e1l_1_bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:gemfile" /></template>
