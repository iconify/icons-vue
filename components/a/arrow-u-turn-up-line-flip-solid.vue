<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftjmqqbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftjmqqbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-u-turn-up-line-flip-solid" /></template>
