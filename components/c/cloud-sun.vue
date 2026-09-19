<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe71zysrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe71zysrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:cloud-sun" /></template>
