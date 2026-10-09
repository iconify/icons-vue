<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clpb2bbyt.css';
import '../../css/t/t5bungbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="clpb2bbyt"/><path class="t5bungbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fish-ladder-48" /></template>
