<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9hum3b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9hum3b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cookie-bite" /></template>
