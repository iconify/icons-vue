<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzwbjzb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzwbjzb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:here" /></template>
