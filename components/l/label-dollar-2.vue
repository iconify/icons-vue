<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utawi2b_n.css';
import '../../css/m/mx3dnrxyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utawi2b_n"/><path clip-rule="evenodd" class="mx3dnrxyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:label-dollar-2" /></template>
