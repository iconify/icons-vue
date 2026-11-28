<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc-l_6bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-l_6bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-to-line-solid" /></template>
