<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyrmry45n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyrmry45n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:comment-sharp" /></template>
