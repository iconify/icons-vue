<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxmzfmt4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxmzfmt4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:animation-plus" /></template>
