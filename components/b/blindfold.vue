<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8s0vi_yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k8s0vi_yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blindfold" /></template>
