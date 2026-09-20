<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idfk1caxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idfk1caxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dwm" /></template>
