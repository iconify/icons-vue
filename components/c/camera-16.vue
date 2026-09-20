<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksrkuob1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ksrkuob1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:camera-16" /></template>
