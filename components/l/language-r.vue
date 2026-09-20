<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js_zqcfan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js_zqcfan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-r" /></template>
