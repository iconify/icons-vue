<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmr362b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nmr362b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:camera" /></template>
