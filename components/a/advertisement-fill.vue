<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thhsj0r-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thhsj0r-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:advertisement-fill" /></template>
