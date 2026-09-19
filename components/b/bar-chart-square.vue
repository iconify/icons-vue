<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8tsarjvu.css';
import '../../css/j/jpoubbo_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8tsarjvu"/><path class="jpoubbo_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bar-chart-square" /></template>
