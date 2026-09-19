<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hinho2lyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hinho2lyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:chevron-right" /></template>
