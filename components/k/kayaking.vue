<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd35nvbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qd35nvbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:kayaking" /></template>
