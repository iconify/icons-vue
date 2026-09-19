<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fon56od1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fon56od1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:camera-alt" /></template>
