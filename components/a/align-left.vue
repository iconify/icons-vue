<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f08tylbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f08tylbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:align-left" /></template>
