<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt0-ruido.css';
import '../../css/b/b8usfzbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pt0-ruido"/><path class="b8usfzbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-20-bold" /></template>
