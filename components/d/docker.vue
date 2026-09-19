<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht1y7-bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":34,"height":24};
const content = `<path class="ht1y7-bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:docker" /></template>
