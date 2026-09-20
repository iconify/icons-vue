<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcvti56rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rcvti56rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chevron-left" /></template>
