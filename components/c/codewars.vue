<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khbe9hban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khbe9hban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:codewars" /></template>
