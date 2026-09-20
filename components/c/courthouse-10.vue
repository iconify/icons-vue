<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fod000b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="fod000b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:courthouse-10" /></template>
