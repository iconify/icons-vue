<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uljo4f1yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="uljo4f1yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-flip-horizontal" /></template>
