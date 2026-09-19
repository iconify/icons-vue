<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1zfhk73w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m1zfhk73w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-twitter" /></template>
