<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oly_l9ycs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oly_l9ycs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:game-2-line" /></template>
