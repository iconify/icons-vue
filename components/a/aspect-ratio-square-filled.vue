<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjef-pb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjef-pb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:aspect-ratio-square-filled" /></template>
