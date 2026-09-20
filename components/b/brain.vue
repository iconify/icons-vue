<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmd2d0b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmd2d0b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brain" /></template>
