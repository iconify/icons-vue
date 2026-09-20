<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnmrr0r5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tnmrr0r5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:eye" /></template>
