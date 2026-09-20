<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aujf7fsah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aujf7fsah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-octagon-solid" /></template>
