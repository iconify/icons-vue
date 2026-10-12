<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4g_2gbsf.css';
import '../../css/v/vixdv7vsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g4g_2gbsf"/><path class="vixdv7vsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:info-circle-stroke-20" /></template>
