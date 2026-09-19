<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycbb76bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycbb76bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:config-map" /></template>
