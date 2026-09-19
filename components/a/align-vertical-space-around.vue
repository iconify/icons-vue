<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwal4_mck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwal4_mck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-vertical-space-around" /></template>
