<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h65wv1-tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h65wv1-tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:base" /></template>
