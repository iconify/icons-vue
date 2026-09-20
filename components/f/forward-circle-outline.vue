<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piuweebqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="piuweebqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:forward-circle-outline" /></template>
