<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di3p_6bnk.css';
import '../../css/t/t8wo_rv6h.css';
import '../../css/v/vkmkxtqch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di3p_6bnk"/><circle class="t8wo_rv6h"/><path class="vkmkxtqch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:fish-outline" /></template>
