<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czo9m703j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="czo9m703j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:hourglass-half" /></template>
