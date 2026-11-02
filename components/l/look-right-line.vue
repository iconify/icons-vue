<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1issgb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1issgb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:look-right-line" /></template>
