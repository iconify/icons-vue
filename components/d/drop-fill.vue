<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tva70obqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tva70obqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drop-fill" /></template>
