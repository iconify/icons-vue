<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcr93w79u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qcr93w79u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:coronation" /></template>
