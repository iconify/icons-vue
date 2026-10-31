<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gef3jd1-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gef3jd1-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-moon-fill-round" /></template>
