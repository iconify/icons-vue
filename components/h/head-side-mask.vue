<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0unyjzng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0unyjzng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:head-side-mask" /></template>
