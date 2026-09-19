<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kydmqcc5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kydmqcc5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:fullscreen-alt" /></template>
