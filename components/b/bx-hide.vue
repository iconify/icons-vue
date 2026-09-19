<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfsjoy2pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfsjoy2pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-hide" /></template>
