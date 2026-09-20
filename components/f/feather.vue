<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi0ta7b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hi0ta7b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:feather" /></template>
