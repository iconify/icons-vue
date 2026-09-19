<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iffb6ably.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iffb6ably"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-dissatisfied-filled" /></template>
