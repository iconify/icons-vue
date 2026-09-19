<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnn65609l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnn65609l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bluetooth" /></template>
