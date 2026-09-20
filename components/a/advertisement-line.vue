<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykgta0_-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykgta0_-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:advertisement-line" /></template>
