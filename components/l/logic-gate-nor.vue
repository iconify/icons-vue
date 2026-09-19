<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an4mqobkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="an4mqobkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:logic-gate-nor" /></template>
