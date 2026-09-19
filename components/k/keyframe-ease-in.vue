<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzu4i-beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzu4i-beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-ease-in" /></template>
