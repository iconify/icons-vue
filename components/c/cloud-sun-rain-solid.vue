<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfl2v5b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfl2v5b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-sun-rain-solid" /></template>
