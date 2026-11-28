<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkbfmobyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkbfmobyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-u-turn-down-solid" /></template>
