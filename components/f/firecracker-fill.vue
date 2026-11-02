<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxk8ojvuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxk8ojvuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:firecracker-fill" /></template>
