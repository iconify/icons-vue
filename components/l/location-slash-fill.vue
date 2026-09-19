<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl-q1cbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yl-q1cbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:location-slash-fill" /></template>
