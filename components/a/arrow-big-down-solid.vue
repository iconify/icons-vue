<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgd4_bb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgd4_bb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-down-solid" /></template>
