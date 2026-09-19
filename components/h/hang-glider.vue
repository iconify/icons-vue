<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcbv8hujb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qcbv8hujb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hang-glider" /></template>
