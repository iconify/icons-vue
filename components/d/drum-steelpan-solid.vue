<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xua8f1yhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xua8f1yhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:drum-steelpan-solid" /></template>
