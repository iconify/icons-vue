<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0ewowbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0ewowbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:haze-2-line" /></template>
