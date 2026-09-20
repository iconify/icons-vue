<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo49cibud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo49cibud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass" /></template>
