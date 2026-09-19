<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn2ia_bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn2ia_bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-sketch" /></template>
