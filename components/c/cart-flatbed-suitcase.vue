<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r76f4fxbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r76f4fxbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cart-flatbed-suitcase" /></template>
