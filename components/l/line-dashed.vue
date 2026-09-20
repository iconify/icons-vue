<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd44gwpip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd44gwpip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:line-dashed" /></template>
