<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d87dqc3wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d87dqc3wl wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-boy-gloss" /></template>
