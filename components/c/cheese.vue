<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4hj5gzwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4hj5gzwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cheese" /></template>
