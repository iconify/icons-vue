<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu6v7ibol.css';
import '../../css/c/c3skeypjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mu6v7ibol"/><path class="c3skeypjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:i-in-square-support-pole" /></template>
