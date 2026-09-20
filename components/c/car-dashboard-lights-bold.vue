<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf6zbp2gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf6zbp2gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:car-dashboard-lights-bold" /></template>
