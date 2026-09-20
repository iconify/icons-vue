<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-h60obbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="y-h60obbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-angular-top-left" /></template>
