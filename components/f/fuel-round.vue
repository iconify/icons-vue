<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flxvxybxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flxvxybxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuel-round" /></template>
