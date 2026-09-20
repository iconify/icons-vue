<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7p0n8gyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7p0n8gyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:elipse-frame" /></template>
