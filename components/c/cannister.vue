<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-cbn8vww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-cbn8vww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cannister" /></template>
