<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rreqimzae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rreqimzae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-4-line" /></template>
