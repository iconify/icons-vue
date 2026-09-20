<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3wzldugj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3wzldugj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-left-up-line" /></template>
