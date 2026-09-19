<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny63qj1dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny63qj1dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:horizontal-split" /></template>
