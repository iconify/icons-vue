<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_dfj-bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_dfj-bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:broken-heart-fill" /></template>
