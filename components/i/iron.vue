<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9e95ubyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9e95ubyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:iron" /></template>
