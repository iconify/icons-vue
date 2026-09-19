<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shie5ja2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shie5ja2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-right-a" /></template>
