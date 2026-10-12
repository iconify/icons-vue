<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zngg8jbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zngg8jbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-horizontal-justify-center-filled" /></template>
