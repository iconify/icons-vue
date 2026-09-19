<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l25j-x-4p.css';
import '../../css/z/z-9vsgwta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l25j-x-4p"/><path class="z-9vsgwta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-backpack" /></template>
