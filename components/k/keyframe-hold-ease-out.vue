<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3beakb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3beakb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-ease-out" /></template>
