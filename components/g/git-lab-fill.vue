<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf4qsvbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf4qsvbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-lab-fill" /></template>
