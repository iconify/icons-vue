<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr91zupuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gr91zupuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:creative-commons-pd" /></template>
