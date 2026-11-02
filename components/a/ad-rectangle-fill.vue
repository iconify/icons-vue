<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfh45bc7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfh45bc7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-rectangle-fill" /></template>
