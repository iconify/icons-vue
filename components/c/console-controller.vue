<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqf1rnq5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqf1rnq5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:console-controller" /></template>
