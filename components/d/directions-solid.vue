<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbt-b3b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hbt-b3b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:directions-solid" /></template>
