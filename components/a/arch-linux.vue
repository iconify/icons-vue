<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0f7r1b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o0f7r1b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:arch-linux" /></template>
