<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un7tcbb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="un7tcbb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:fedora" /></template>
