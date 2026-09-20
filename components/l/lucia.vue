<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz4p5n3yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz4p5n3yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lucia" /></template>
