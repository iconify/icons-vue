<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g98ny67fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g98ny67fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:equalizer-3-line" /></template>
