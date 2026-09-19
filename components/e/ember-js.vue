<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1eoc3ohu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1eoc3ohu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:ember-js" /></template>
