<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9ze3t4ye.css';
import '../../css/k/kztogd7av.css';
import '../../css/x/x6gqxacdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ze3t4ye"/><path class="kztogd7av"/><path class="x6gqxacdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:camera-double" /></template>
