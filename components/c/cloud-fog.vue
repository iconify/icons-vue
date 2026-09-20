<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc2q1fbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc2q1fbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cloud-fog" /></template>
