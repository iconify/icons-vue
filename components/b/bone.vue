<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iik494jlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iik494jlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bone" /></template>
