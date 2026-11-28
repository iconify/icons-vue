<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw520ebla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw520ebla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-ellipsis-solid" /></template>
