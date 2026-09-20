<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-qz-097d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-qz-097d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:500px-logo-1" /></template>
