<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsy6j0bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fsy6j0bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hourglass-empty" /></template>
