<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svx0lxokl.css';
import '../../css/d/dgfy8elcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary svx0lxokl"/><path class="dgfy8elcu primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-right-duo" /></template>
