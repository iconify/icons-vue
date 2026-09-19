<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-s8crb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x-s8crb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:directions-sign-1" /></template>
