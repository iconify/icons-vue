<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twga4rbxo.css';
import '../../css/l/ltcgo_b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="twga4rbxo"/><path class="ltcgo_b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brine-pond-48" /></template>
