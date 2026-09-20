<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppivl6_do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ppivl6_do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:m" /></template>
