<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo_bad7tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo_bad7tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:checkerboard-plus" /></template>
