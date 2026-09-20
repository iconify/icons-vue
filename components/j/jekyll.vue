<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4x5_tbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4x5_tbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jekyll" /></template>
