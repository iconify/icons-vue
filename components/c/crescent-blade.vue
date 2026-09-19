<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy3p43tkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sy3p43tkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crescent-blade" /></template>
