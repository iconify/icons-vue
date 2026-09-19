<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kuisey8iv.css';
import '../../css/v/vkprnmhcj.css';
import '../../css/m/mi0sarbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kuisey8iv"/><path class="vkprnmhcj"/><path class="mi0sarbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:apron" /></template>
