<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kftm6xogs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kftm6xogs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon" /></template>
