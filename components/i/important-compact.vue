<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhj_eqnyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yhj_eqnyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:important-compact" /></template>
