<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu_3q2bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu_3q2bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:helmet-solid" /></template>
