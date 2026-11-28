<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrp8x2bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrp8x2bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bowl" /></template>
