<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2uy08i6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="w2uy08i6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-up" /></template>
