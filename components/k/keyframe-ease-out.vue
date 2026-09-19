<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgkbm7kca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgkbm7kca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-ease-out" /></template>
