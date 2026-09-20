<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn3fnbnbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn3fnbnbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drive-line" /></template>
