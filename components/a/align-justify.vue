<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3uxh5b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q3uxh5b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:align-justify" /></template>
