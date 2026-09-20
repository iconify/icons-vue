<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2i9psbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2i9psbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:book-24" /></template>
