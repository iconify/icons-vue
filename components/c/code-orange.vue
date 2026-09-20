<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mghtvdb9z.css';
import '../../css/s/s_h41w30n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mghtvdb9z"/><path class="s_h41w30n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:code-orange" /></template>
