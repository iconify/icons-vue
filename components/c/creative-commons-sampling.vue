<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqo8ecpat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hqo8ecpat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:creative-commons-sampling" /></template>
