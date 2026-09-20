<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyvn7-bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nyvn7-bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:language-python" /></template>
