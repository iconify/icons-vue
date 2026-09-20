<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-guoyy4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-guoyy4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:aircraft-hot-air-balloon-2-bold" /></template>
