<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-lwsub9k.css';
import '../../css/e/e3net-b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l-lwsub9k"/><path class="e3net-b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:heartblue" /></template>
