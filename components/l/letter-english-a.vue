<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_0stws9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_0stws9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:letter-english-a" /></template>
