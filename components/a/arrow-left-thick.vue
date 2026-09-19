<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av4w2sb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av4w2sb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:arrow-left-thick" /></template>
