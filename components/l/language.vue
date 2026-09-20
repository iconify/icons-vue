<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glx_78vkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="glx_78vkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:language" /></template>
