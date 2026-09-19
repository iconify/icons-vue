<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt2ou9bdc.css';
import '../../css/y/yvd4i4bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt2ou9bdc"/><path class="yvd4i4bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-home-heart" /></template>
