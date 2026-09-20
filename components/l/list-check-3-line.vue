<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2vhfe_ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2vhfe_ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-3-line" /></template>
