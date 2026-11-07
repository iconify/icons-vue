<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfdoik__w.css';
import '../../css/m/m_qerhonx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kfdoik__w"/><path class="m_qerhonx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:import-bold" /></template>
