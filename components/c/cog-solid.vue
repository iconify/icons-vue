<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioq918dwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioq918dwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cog-solid" /></template>
