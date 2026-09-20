<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg1bwt3th.css';
import '../../css/d/dxvormbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kg1bwt3th"/><path class="dxvormbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-contract" /></template>
