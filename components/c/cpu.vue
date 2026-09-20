<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy7f59chl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oy7f59chl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cpu" /></template>
