<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zipr6oyhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zipr6oyhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:camera-nomotion" /></template>
