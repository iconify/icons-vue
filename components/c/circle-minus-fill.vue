<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycafcjx8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ycafcjx8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-minus-fill" /></template>
