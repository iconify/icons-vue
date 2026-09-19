<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqc0ucc7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tqc0ucc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:life-support" /></template>
