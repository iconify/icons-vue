<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu3t20bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu3t20bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-split-horizontal-bold" /></template>
