<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h26g72gzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h26g72gzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:column-fill" /></template>
