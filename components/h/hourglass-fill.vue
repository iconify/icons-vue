<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7--l_xes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7--l_xes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-fill" /></template>
