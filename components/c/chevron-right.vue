<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiuqq6-6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiuqq6-6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chevron-right" /></template>
