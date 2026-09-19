<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zugda47zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zugda47zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:glide" /></template>
