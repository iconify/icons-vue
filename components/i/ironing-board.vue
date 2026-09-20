<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebs3ndmsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebs3ndmsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:ironing-board" /></template>
