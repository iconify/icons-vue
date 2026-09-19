<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqrder4yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hqrder4yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:laravel-wordmark" /></template>
