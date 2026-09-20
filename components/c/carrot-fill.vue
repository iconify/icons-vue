<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv3p--bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv3p--bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:carrot-fill" /></template>
