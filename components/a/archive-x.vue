<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk3763b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk3763b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:archive-x" /></template>
