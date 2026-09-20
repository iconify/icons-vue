<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvh8l4olr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvh8l4olr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-minus" /></template>
