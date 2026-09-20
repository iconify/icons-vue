<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk54m3b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk54m3b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:diamond" /></template>
