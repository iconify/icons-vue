<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6_co0ppv.css';
import '../../css/t/t5k-_f5ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6_co0ppv"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-outline" /></template>
