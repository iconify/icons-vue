<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyy0mledw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyy0mledw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:button-play-bold" /></template>
