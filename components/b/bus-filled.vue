<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dplxyhb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dplxyhb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bus-filled" /></template>
