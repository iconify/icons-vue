<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_9sazb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x_9sazb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-justify-20" /></template>
