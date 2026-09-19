<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0ruxsi2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0ruxsi2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:dell" /></template>
