<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yla03qffw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yla03qffw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flag-on-flag-handle-above-railway-track" /></template>
