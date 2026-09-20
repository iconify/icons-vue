<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxud8ntgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxud8ntgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:betterdiscord" /></template>
