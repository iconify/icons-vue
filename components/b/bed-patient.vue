<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0n8e72ao.css';
import '../../css/y/yk0g4yont.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0n8e72ao"/><path class="yk0g4yont"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bed-patient" /></template>
