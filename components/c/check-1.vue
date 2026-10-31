<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqyhy9bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqyhy9bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:check-1" /></template>
