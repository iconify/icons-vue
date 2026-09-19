<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvf2knbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvf2knbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cross-circle" /></template>
