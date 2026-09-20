<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmir9_bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmir9_bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:juce" /></template>
