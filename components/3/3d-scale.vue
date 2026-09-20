<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cidenrbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cidenrbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:3d-scale" /></template>
