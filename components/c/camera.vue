<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ful1m9b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ful1m9b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:camera" /></template>
