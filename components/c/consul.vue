<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyb02xdma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyb02xdma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:consul" /></template>
