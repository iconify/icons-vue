<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxcil-b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxcil-b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hard-drive-solid" /></template>
