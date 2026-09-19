<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdovg_p_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdovg_p_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:jumping-rope" /></template>
