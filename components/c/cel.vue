<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlb-sobmx.css';
import '../../css/f/fv0846l_k.css';
import '../../css/m/m_fk-ibei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlb-sobmx"/><path class="fv0846l_k"/><path class="m_fk-ibei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cel" /></template>
