<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af6ze-elo.css';
import '../../css/v/vgqa32bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="af6ze-elo"/><path class="vgqa32bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cpu-20" /></template>
