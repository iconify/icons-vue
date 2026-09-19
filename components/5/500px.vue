<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaqj09b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="aaqj09b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:500px" /></template>
