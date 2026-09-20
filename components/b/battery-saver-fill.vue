<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfuj10bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfuj10bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-saver-fill" /></template>
