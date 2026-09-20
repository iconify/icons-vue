<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkw7e0b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="tkw7e0b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:euro" /></template>
