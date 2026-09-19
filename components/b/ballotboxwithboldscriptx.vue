<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m640zw-kt.css';
import '../../css/s/s4s4c3b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m640zw-kt"/><path class="s4s4c3b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ballotboxwithboldscriptx" /></template>
