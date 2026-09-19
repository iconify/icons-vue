<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksvyc4bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1216,"height":1632};
const content = `<path class="ksvyc4bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:door-closed" /></template>
