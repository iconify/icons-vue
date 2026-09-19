<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m640zw-kt.css';
import '../../css/h/h4318abpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m640zw-kt"/><path class="h4318abpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:ballotboxboldcheck" /></template>
