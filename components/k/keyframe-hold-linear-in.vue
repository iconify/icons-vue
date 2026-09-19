<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnitxibej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnitxibej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-linear-in" /></template>
