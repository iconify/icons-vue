<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp7zgxjuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp7zgxjuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:graduation-cap" /></template>
