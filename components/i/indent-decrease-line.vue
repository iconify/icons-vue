<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-b_krv-u.css';
import '../../css/s/s99lf0bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-b_krv-u"/><path class="s99lf0bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:indent-decrease-line" /></template>
