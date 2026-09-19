<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm0vp1ieb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm0vp1ieb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:aws" /></template>
