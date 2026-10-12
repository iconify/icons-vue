<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baq8k5bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="baq8k5bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:camera-fill-20" /></template>
