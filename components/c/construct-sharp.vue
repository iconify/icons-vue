<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouaf7fzvu.css';
import '../../css/v/vvr-kwzju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouaf7fzvu"/><path class="vvr-kwzju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:construct-sharp" /></template>
