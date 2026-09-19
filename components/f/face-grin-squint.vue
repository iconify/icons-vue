<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5rpv5guj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5rpv5guj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-grin-squint" /></template>
