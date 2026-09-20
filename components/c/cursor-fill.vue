<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr6ru96_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr6ru96_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-fill" /></template>
