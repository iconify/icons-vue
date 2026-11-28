<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9tw53b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9tw53b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bone-solid" /></template>
