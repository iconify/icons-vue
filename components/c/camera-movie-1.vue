<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcu0apbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="zcu0apbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:camera-movie-1" /></template>
