<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggysgtp2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ggysgtp2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:github-square" /></template>
