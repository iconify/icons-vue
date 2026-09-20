<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itj2tfnbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itj2tfnbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:archive-stack-fill" /></template>
