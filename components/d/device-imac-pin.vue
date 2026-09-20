<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvh1ohb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvh1ohb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-pin" /></template>
