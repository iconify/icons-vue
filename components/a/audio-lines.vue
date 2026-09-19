<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xilkr0bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xilkr0bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:audio-lines" /></template>
