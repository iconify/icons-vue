<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfm6tob8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rfm6tob8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bed-bunk-duotone" /></template>
