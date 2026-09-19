<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqd2_6pjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oqd2_6pjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ladybug" /></template>
