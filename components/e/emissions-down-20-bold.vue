<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onux0z-vm.css';
import '../../css/f/f5m_ylwro.css';
import '../../css/v/vvusakkjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="onux0z-vm"/><path class="f5m_ylwro"/><path class="vvusakkjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emissions-down-20-bold" /></template>
