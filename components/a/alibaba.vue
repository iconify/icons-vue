<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn4jr074g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn4jr074g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:alibaba" /></template>
