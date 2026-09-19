<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax7zwolhm.css';
import '../../css/a/ant9fwtwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax7zwolhm"/><path class="ant9fwtwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:big-data-outlined" /></template>
