<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx6-ebbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx6-ebbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-end-horizontal-sharp" /></template>
