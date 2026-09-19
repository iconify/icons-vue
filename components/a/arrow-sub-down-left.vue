<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrc_9q2ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrc_9q2ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-sub-down-left" /></template>
