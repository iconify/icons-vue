<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzveq5_2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uzveq5_2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:camera-reverse-sharp" /></template>
