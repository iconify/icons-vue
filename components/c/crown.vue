<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5gajwboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5gajwboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:crown" /></template>
