<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbzy___-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbzy___-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-h-octagon" /></template>
