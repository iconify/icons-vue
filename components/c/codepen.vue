<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdr9b6yaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdr9b6yaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:codepen" /></template>
