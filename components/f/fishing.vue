<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf-vh0nte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf-vh0nte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fishing" /></template>
