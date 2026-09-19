<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjhhafq6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjhhafq6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:coins-stack" /></template>
