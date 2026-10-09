<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shozmhblo.css';
import '../../css/e/ex4r6bbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="shozmhblo"/><path class="ex4r6bbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fusion-20-bold" /></template>
