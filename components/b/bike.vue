<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-9hypb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-9hypb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bike" /></template>
