<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsn9p1b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nsn9p1b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:keybase" /></template>
