<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or9gezb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="or9gezb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chrome" /></template>
