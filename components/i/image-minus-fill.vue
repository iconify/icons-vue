<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8jm71bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8jm71bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:image-minus-fill" /></template>
