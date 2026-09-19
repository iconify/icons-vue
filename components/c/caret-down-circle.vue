<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgtzwm3rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgtzwm3rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-down-circle" /></template>
