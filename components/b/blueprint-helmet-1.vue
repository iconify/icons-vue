<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwyl8uboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwyl8uboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:blueprint-helmet-1" /></template>
