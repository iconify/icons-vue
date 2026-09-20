<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f29ecibga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f29ecibga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:document-layout-left" /></template>
