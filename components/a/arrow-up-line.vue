<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gapgg0w6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gapgg0w6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-line" /></template>
